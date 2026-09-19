<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-fn4_ybf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="g-fn4_ybf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:trash-can" {...props}></Icon>
