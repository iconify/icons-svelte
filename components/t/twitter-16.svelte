<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzgdiwbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dzgdiwbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:twitter-16" {...props}></Icon>
