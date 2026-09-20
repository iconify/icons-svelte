<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5rgj7ipz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b5rgj7ipz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:switch-filled" {...props}></Icon>
