Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 16:35:04 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/navdeeptura/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_16:32:18] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_16:32:24] STEP 2: Create topics started

  [INFO 2024-12-05_16:32:43] STEP 2: Completed

  [INFO 2024-12-05_16:32:53] STEP 3: producing data started

  [INFO 2024-12-05_16:32:57] MQTT connection established...

  [INFO 2024-12-05_16:32:58] STEP 4: Preprocessing started

  [INFO 2024-12-05_16:33:01] STEP 4: Preprocessing started

  [INFO 2024-12-05_16:33:03] STEP 7: Visualization started

  [INFO 2024-12-05_16:33:09] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_16:33:23] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_16:33:27] STEP 8: Starting docker push for: navdeeptura/groupproject4dec-11f8-amd64

  [INFO 2024-12-05_16:33:36] STEP 9: Starting privateGPT

  [INFO 2024-12-05_16:33:46] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_16:33:56] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 338bef562eaf navdeeptura/groupproject4dec-11f8-amd64 - message=0

  [INFO 2024-12-05_16:34:42] STEP 8: Successfully ran Docker push: docker push navdeeptura/groupproject4dec-11f8-amd64 - message=0

  [INFO 2024-12-05_16:35:04] STEP 10: Started to build the documentation

  [INFO 2024-12-05_16:35:05] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


