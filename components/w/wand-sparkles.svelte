<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eahi3-bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eahi3-bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:wand-sparkles" {...props}></Icon>
