<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_09tab4h.css';
import '../../css/c/c807_0blv.css';
import '../../css/n/ns1f0lben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_09tab4h"/><path class="c807_0blv"/><path class="ns1f0lben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:viva-engage-logo" {...props}></Icon>
