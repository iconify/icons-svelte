<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrj54obkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lrj54obkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:star-on" {...props}></Icon>
