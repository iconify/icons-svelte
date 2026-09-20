<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq_gakbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zq_gakbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:tab-a" {...props}></Icon>
