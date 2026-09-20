<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fofqrabvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fofqrabvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:spark-line" {...props}></Icon>
