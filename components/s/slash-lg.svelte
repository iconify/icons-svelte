<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj4eti7ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dj4eti7ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:slash-lg" {...props}></Icon>
