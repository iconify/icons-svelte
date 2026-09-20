<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc229nbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sc229nbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:warehouse-into-filled" {...props}></Icon>
