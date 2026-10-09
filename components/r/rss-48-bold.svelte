<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9xxoy94z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a9xxoy94z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rss-48-bold" {...props}></Icon>
