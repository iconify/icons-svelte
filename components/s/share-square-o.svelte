<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9wjtwlcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1536};
const content = `<path class="e9wjtwlcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:share-square-o" {...props}></Icon>
