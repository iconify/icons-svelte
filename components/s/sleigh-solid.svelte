<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcsa_x5rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vcsa_x5rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:sleigh-solid" {...props}></Icon>
