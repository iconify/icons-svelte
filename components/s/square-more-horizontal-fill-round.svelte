<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmfxnmbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmfxnmbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-more-horizontal-fill-round" {...props}></Icon>
