<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehiw4ce2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ehiw4ce2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:share" {...props}></Icon>
