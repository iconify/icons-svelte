<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_yzbdcai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h_yzbdcai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:seek-backward-16" {...props}></Icon>
