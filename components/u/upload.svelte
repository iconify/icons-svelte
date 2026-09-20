<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h02zmjtek.css';
import '../../css/q/qy0rpabfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h02zmjtek"/><path class="qy0rpabfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:upload" {...props}></Icon>
