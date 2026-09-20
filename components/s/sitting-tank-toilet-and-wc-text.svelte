<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfwbx1x2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jfwbx1x2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sitting-tank-toilet-and-wc-text" {...props}></Icon>
