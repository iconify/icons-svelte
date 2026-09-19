<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc9rbmb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xc9rbmb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:snort" {...props}></Icon>
