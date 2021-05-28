# Achilles and the tortoise

## Requirements

- [Visual Studio Code](https://code.visualstudio.com/) and the [Remote container extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers).
- [Docker](https://www.docker.com/get-started) must be pre-installed on the machine.
- The repository `devcontainer` setup requires `docker-compose` to be installed on the machine.

## How to configure Visual Studio Code to run the demos

Once configuration is completed VS Code will show a new `Ports` tab, in the bottom-docked terminal area. The `Ports` tab will list all the ports exposed by the remote containers.

### Verify that setup completed successfully

Locate Visual Studio Code `Ports` tab. The tab by default shows four columns, `Port`, `Local Address`, `Running Process`, and `Origin`.

- Locate the row, in the `Port` column, containing the value `15672` (the RabbitMQ management port).
- Hover the located row with the mouse and click on the `Open in Browser` icon in the `Local Address` column.
- A new browser tab is opened and the RabbitMQ management page is displayed.

The following section contains connection information details.

## Containers connection information

The default RabbitMQ credentials are:

- Username: `guest`
- Password: `guest`

## Repository structure

...

## Workshop 1

In this workshop we will introduce RabbitMQ and we will get our hands on the `setupQueue.ts` inside `producer` folder.

Before execute the `setupQueue.ts` script with `yarn setup-queue`, install all dependencies running `yarn`.
