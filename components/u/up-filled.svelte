<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-2-sq4wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j-2-sq4wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:up-filled" {...props}></Icon>
