<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awbxz5bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="awbxz5bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:water-bathing" {...props}></Icon>
