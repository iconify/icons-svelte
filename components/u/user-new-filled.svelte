<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htbowudik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="htbowudik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:user-new-filled" {...props}></Icon>
