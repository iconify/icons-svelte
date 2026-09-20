<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpi9kab-u.css';
import '../../css/k/kpwcb-rgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wpi9kab-u"/><path class="kpwcb-rgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:wireless-disabled-16" {...props}></Icon>
