<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmnnnw1xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zmnnnw1xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:runson" {...props}></Icon>
