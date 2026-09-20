<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghzt9mbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ghzt9mbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sipeed-dark" {...props}></Icon>
