<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vikf1-blz.css';
import '../../css/n/nt60jabuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="vikf1-blz"/><path class="nt60jabuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-odnoklassniki" {...props}></Icon>
