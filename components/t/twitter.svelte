<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d24y88b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":209};
const content = `<path class="d24y88b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:twitter" {...props}></Icon>
