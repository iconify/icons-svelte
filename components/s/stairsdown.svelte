<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6-wb4b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k6-wb4b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:stairsdown" {...props}></Icon>
