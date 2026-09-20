<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glyc36bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="glyc36bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:stamp" {...props}></Icon>
