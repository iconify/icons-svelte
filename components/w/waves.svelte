<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdv-he75m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xdv-he75m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:waves" {...props}></Icon>
