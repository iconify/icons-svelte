<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe27yw0co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fe27yw0co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:triangle-up-filled" {...props}></Icon>
