<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh-qmcohf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rh-qmcohf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:sailboat" {...props}></Icon>
