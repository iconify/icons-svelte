<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwaz_k85j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwaz_k85j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:snowpack" {...props}></Icon>
