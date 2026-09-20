<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1t7rbc-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o1t7rbc-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:star" {...props}></Icon>
