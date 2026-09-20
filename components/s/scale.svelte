<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhbc-n8wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dhbc-n8wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:scale" {...props}></Icon>
