<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0hie25hf.css';
import '../../css/a/asxl2zw-h.css';
import '../../css/v/vf565cbtz.css';
import '../../css/w/wcz1y7biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h0hie25hf"/><path class="asxl2zw-h"/><path class="vf565cbtz"/><path class="wcz1y7biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shovel-20-bold" {...props}></Icon>
