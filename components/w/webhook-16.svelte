<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yor0a7bzn.css';
import '../../css/h/hir2mbb0k.css';
import '../../css/h/hj176wbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yor0a7bzn"/><path class="hir2mbb0k"/><path class="hj176wbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:webhook-16" {...props}></Icon>
