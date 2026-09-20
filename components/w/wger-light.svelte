<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpntpub6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cpntpub6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wger-light" {...props}></Icon>
