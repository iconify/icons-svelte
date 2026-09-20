<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqsu-ibjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqsu-ibjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wardrobe-line" {...props}></Icon>
