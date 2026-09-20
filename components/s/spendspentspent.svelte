<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj16trbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zj16trbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spendspentspent" {...props}></Icon>
