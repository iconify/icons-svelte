<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pup2v7bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pup2v7bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:speaker-3" {...props}></Icon>
