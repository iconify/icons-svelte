<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xubdi0bqd.css';
import '../../css/w/wkhlrxb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="xubdi0bqd"/><path class="wkhlrxb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="geo:turf-buffer" {...props}></Icon>
