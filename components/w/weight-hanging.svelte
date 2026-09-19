<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_3appbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="i_3appbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:weight-hanging" {...props}></Icon>
