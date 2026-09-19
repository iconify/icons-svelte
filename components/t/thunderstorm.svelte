<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r47ofacoh.css';
import '../../css/k/kya3ihb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r47ofacoh"/><path class="kya3ihb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:thunderstorm" {...props}></Icon>
