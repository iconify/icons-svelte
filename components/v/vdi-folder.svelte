<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3uc9rd7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3uc9rd7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:vdi-folder" {...props}></Icon>
