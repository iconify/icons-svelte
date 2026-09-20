<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arb81b3en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="arb81b3en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:sort-vertical" {...props}></Icon>
