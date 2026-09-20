<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6hgihjwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":263};
const content = `<path class="o6hgihjwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:unity-dark" {...props}></Icon>
