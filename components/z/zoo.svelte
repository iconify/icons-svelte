<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki_xp1ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ki_xp1ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:zoo" {...props}></Icon>
