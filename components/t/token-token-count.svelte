<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwzs1uccg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kwzs1uccg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-token-count" {...props}></Icon>
