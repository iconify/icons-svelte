<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyh-adcgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyh-adcgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wiper-line" {...props}></Icon>
