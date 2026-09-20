<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e65-adcad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e65-adcad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-rainbow-outline" {...props}></Icon>
