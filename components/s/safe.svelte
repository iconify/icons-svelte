<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwf_e237l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fwf_e237l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:safe" {...props}></Icon>
