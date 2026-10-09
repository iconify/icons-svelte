<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxp4m9b4u.css';
import '../../css/g/goglxpbft.css';
import '../../css/j/j8jzh-cpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cxp4m9b4u"/><path class="goglxpbft"/><path class="j8jzh-cpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:substation-48" {...props}></Icon>
