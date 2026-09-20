<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi-03_b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi-03_b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:rss-outline" {...props}></Icon>
