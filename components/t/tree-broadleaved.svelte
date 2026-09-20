<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh6p_1bdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dh6p_1bdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:tree-broadleaved" {...props}></Icon>
