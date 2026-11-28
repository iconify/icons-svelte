<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn7jzcrio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn7jzcrio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:rss-check" {...props}></Icon>
