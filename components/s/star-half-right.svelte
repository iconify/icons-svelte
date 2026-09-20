<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssld43bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ssld43bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:star-half-right" {...props}></Icon>
