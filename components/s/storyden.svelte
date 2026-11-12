<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl7-i1bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nl7-i1bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:storyden" {...props}></Icon>
