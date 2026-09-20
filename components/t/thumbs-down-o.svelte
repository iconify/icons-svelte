<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1df35b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x1df35b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:thumbs-down-o" {...props}></Icon>
