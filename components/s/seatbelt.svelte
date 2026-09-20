<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r59kf3bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="r59kf3bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:seatbelt" {...props}></Icon>
