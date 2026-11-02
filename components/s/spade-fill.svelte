<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0lhnbbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0lhnbbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spade-fill" {...props}></Icon>
