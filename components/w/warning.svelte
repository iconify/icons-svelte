<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giwi5ubbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="giwi5ubbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:warning" {...props}></Icon>
