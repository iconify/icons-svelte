<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9o6g8dcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v9o6g8dcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:volume-mute-filled" {...props}></Icon>
