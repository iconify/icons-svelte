<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olsgh7b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="olsgh7b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:twitter" {...props}></Icon>
