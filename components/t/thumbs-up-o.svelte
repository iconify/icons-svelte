<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw644_pji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vw644_pji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:thumbs-up-o" {...props}></Icon>
