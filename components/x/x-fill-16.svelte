<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7h3bczat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p7h3bczat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:x-fill-16" {...props}></Icon>
