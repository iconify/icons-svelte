<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgsqg7sjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lgsqg7sjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitedownpointinglefthand" {...props}></Icon>
