<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i18l58b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="i18l58b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-youtube" {...props}></Icon>
