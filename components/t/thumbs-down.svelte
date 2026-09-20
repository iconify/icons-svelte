<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g88r1cckn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g88r1cckn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:thumbs-down" {...props}></Icon>
