<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg-dnlbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg-dnlbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:save" {...props}></Icon>
