<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3du-fbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="k3du-fbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:vpn-connection-remix" {...props}></Icon>
