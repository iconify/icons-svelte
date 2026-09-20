<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpy_g2b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jpy_g2b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:x-p-ferd-light" {...props}></Icon>
