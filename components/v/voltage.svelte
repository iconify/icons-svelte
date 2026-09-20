<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuounlbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tuounlbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:voltage" {...props}></Icon>
