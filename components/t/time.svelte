<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h02-0zi4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h02-0zi4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:time" {...props}></Icon>
