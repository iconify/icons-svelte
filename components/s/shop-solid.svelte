<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgk4045dp.css';
import '../../css/e/e26d43smq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mgk4045dp"/><path class="e26d43smq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:shop-solid" {...props}></Icon>
