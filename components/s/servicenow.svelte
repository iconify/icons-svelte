<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuomrd10d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="uuomrd10d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:servicenow" {...props}></Icon>
