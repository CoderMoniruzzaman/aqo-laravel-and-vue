import a
    from '../../../vendor/phpunit/php-code-coverage/src/Report/Html/Renderer/Template/js/nv.d3.min';
import { Button } from '../../../public/js/app';
<template>
    <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="card">
              <div class="card-header">
                <h3 class="card-title">User List</h3>

                <div class="card-tools">
                <Button type="" class="btn btn-success " data-toggle="modal" data-target="#addNew">Add New <i class="fas fa-user-plus fa-fw"></i></Button>
                </div>
              </div>
              <!-- /.card-header -->
              <div class="card-body table-responsive p-0">
                <table class="table table-hover text-nowrap">
                  <thead>
                    <tr>
                      <th>ID</th>
                      <th>Name</th>
                      <th>Email</th>
                      <th>Type</th>
                      <th>Modify</th>
                    </tr>
                  </thead>
                  <tbody>
                    <tr>
                      <td>183</td>
                      <td>John Doe</td>
                      <td>11-7-2014</td>
                      <td><span class="tag tag-success">Approved</span></td>
                      <td>
                        <a href="#">Edit
                            <i class="fa fa-edit mr-1"></i>
                        </a>

                        <a href="#">Trash
                            <i class="fa fa-trash mr-1"></i>
                        </a>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
              <!-- /.card-body -->
            </div>
            <!-- /.card -->
          </div>
        </div>


    <!-- Modal -->
        <div class="modal fade" id="addNew" tabindex="-1" role="dialog" aria-labelledby="addNewLabel" aria-hidden="true">
            <div class="modal-dialog  modal-dialog-centered" role="document">
                <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="addNewLabel">Modal title</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                    <span aria-hidden="true">&times;</span>
                    </button>
                </div>
                <div class="modal-body">
                    ...
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-danger" data-dismiss="modal">Close</button>
                    <button type="button" class="btn btn-primary">Create</button>
                </div>
                </div>
            </div>
        </div>

    </div>
    
</template>

<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
