<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl7y_pp3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl7y_pp3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:rss" {...props}></Icon>
