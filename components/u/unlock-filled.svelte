<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge79lcctt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ge79lcctt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:unlock-filled" {...props}></Icon>
