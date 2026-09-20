<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd4g7om-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xd4g7om-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:star-half-16" {...props}></Icon>
