<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-5ensbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-5ensbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-search-filled" {...props}></Icon>
