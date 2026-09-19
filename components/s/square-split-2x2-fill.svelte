<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz19t2nyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nz19t2nyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:square-split-2x2-fill" {...props}></Icon>
