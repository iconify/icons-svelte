<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhdo3bc4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhdo3bc4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tumblr-filled" {...props}></Icon>
