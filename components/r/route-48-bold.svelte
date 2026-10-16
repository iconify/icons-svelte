<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb93embdy.css';
import '../../css/j/jmov7dbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lb93embdy"/><path class="jmov7dbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:route-48-bold" {...props}></Icon>
