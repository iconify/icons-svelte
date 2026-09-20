<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecsb_ubac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ecsb_ubac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:theater-masks-solid" {...props}></Icon>
