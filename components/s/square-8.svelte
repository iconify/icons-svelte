<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihpmtnj8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihpmtnj8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:square-8" {...props}></Icon>
