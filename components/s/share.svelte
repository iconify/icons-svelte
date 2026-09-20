<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwurh4b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jwurh4b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:share" {...props}></Icon>
