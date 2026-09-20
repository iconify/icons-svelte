<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uee9srb7s.css';
import '../../css/l/l1wv36b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":254.6,"height":253.5};
const content = `<path class="uee9srb7s"/><path class="l1wv36b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tesla-dark" {...props}></Icon>
