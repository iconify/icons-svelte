<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it4grp-4n.css';
import '../../css/h/hk3jr4mxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="it4grp-4n"/><path class="hk3jr4mxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tailings-dam-48-bold" {...props}></Icon>
