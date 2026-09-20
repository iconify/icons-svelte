<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4le9wpeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4le9wpeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:volume-plus" {...props}></Icon>
