<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrhq8kw0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mrhq8kw0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-package" {...props}></Icon>
