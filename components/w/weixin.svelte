<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfxd2tr0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="bfxd2tr0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:weixin" {...props}></Icon>
