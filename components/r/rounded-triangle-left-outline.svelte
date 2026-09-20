<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcyejvb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qcyejvb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-triangle-left-outline" {...props}></Icon>
