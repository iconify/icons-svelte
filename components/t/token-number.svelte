<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-t8zubqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x-t8zubqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-number" {...props}></Icon>
