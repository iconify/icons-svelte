<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mun4s9bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mun4s9bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:syllabary-hangul" {...props}></Icon>
