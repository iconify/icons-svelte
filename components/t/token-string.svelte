<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a45phhb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a45phhb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-string" {...props}></Icon>
