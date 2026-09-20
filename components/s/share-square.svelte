<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvke21biv.css';
import '../../css/y/y__gdjb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rvke21biv"/><path class="y__gdjb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:share-square" {...props}></Icon>
