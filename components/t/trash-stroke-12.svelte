<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e12qxeb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e12qxeb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:trash-stroke-12" {...props}></Icon>
