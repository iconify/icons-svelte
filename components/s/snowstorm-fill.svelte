<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9it0y2ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9it0y2ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowstorm-fill" {...props}></Icon>
