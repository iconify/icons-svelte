<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvrx7uf1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vvrx7uf1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:rss-fill" {...props}></Icon>
