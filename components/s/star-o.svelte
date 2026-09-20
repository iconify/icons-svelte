<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-fl9ri0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n-fl9ri0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:star-o" {...props}></Icon>
