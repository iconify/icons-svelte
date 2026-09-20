<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzxikebty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzxikebty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:swiper" {...props}></Icon>
