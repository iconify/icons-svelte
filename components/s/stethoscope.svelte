<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9l4enb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a9l4enb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:stethoscope" {...props}></Icon>
