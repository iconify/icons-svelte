<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-vb4pags.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-vb4pags"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vectorworks" {...props}></Icon>
