<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsumi_t5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xsumi_t5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:steam" {...props}></Icon>
