<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy2xwebtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sy2xwebtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:typescript" {...props}></Icon>
