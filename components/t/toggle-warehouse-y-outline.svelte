<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5muy2b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b5muy2b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:toggle-warehouse-y-outline" {...props}></Icon>
