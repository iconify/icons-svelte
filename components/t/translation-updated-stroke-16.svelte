<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfdo2-b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kfdo2-b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-updated-stroke-16" {...props}></Icon>
