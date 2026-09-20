<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic4sspakf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ic4sspakf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:twitter" {...props}></Icon>
