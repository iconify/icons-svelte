<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hia19evqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="hia19evqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-tumblr" {...props}></Icon>
