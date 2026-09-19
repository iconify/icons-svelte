<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9oq_pbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j9oq_pbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:shopping-cart" {...props}></Icon>
