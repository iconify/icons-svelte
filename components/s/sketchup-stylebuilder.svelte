<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hto5tzmnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":482,"height":512};
const content = `<path class="hto5tzmnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sketchup-stylebuilder" {...props}></Icon>
