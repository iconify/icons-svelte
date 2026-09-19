<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akdnkpb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":940,"height":614};
const content = `<path class="akdnkpb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:yahoo" {...props}></Icon>
