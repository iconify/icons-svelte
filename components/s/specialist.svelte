<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6f3mn3in.css';
import '../../css/z/zw6fdactm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r6f3mn3in"/><path class="zw6fdactm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:specialist" {...props}></Icon>
