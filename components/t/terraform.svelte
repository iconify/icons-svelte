<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsk9_xzju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":72};
const content = `<path class="xsk9_xzju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:terraform" {...props}></Icon>
