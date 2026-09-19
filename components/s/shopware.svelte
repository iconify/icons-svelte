<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x213hpcka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x213hpcka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:shopware" {...props}></Icon>
