<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlc_msnzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlc_msnzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-leo-fill-round" {...props}></Icon>
