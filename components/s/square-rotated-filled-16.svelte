<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhyb4abqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yhyb4abqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:square-rotated-filled-16" {...props}></Icon>
