<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxnf1q5gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lxnf1q5gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sort-filled" {...props}></Icon>
