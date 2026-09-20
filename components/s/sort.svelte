<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thv0p7btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="thv0p7btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:sort" {...props}></Icon>
