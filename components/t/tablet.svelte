<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2u8uksmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x2u8uksmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:tablet" {...props}></Icon>
