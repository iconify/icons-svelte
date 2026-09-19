<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxm34-kzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":460,"height":512};
const content = `<path class="vxm34-kzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:searchengin" {...props}></Icon>
