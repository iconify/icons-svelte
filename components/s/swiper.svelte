<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj481d2gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kj481d2gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:swiper" {...props}></Icon>
