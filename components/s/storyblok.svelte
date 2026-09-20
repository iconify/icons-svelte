<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk487_b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":302};
const content = `<path class="pk487_b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:storyblok" {...props}></Icon>
