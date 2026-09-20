<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t99oo8baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":499.614};
const content = `<path class="t99oo8baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stc" {...props}></Icon>
