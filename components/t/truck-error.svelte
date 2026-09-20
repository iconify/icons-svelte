<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbqbpxnyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbqbpxnyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-error" {...props}></Icon>
