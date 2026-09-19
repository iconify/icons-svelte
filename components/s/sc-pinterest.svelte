<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhskczy5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="lhskczy5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-pinterest" {...props}></Icon>
