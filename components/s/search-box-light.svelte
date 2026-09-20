<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujd6pxb0p.css';
import '../../css/k/k35tmdb5w.css';
import '../../css/k/k4leaeb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujd6pxb0p"/><path class="k35tmdb5w"/><path class="k4leaeb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-box-light" {...props}></Icon>
