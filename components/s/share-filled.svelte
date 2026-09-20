<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8_j0_bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b8_j0_bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:share-filled" {...props}></Icon>
