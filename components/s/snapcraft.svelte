<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv6_idbzi.css';
import '../../css/h/hcv589g6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1.28,"height":1.28};
const content = `<path class="vv6_idbzi"/><path class="hcv589g6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:snapcraft" {...props}></Icon>
