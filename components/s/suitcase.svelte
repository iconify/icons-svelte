<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcsms5bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bcsms5bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:suitcase" {...props}></Icon>
