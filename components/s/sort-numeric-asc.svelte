<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kic8bacdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kic8bacdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sort-numeric-asc" {...props}></Icon>
