<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am2cvt6mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="am2cvt6mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whisparr-light" {...props}></Icon>
