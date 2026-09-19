<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0s0by2sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="o0s0by2sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-soundcloud" {...props}></Icon>
