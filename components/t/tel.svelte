<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5qgjt1uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="p5qgjt1uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:tel" {...props}></Icon>
