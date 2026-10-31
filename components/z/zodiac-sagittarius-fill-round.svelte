<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iin4xh33f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iin4xh33f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-sagittarius-fill-round" {...props}></Icon>
