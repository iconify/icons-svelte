<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4h35nmyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="z4h35nmyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-telegram" {...props}></Icon>
