<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6kyc2-vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="a6kyc2-vd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-twitter" {...props}></Icon>
