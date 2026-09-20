<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsrrl1ges.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gsrrl1ges"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:vertical-center-filled" {...props}></Icon>
