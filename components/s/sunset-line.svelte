<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev35-acdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev35-acdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sunset-line" {...props}></Icon>
