<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni1alsbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ni1alsbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xwiki-dark" {...props}></Icon>
