<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-z3noepd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i-z3noepd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:search-outline" {...props}></Icon>
