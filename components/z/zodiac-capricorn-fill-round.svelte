<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd5mfab7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd5mfab7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-capricorn-fill-round" {...props}></Icon>
