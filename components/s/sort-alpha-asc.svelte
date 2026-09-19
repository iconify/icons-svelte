<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0e143blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1632,"height":1792};
const content = `<path class="u0e143blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:sort-alpha-asc" {...props}></Icon>
