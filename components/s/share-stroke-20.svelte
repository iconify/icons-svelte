<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tso6gqw6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tso6gqw6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:share-stroke-20" {...props}></Icon>
