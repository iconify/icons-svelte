<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyknwlbkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":82,"height":64};
const content = `<path clip-rule="evenodd" class="wyknwlbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sst" {...props}></Icon>
