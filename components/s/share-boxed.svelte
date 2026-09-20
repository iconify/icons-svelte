<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-ul5rahn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d-ul5rahn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:share-boxed" {...props}></Icon>
