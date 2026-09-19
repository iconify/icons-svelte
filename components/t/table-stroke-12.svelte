<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9nk1jhad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="f9nk1jhad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:table-stroke-12" {...props}></Icon>
