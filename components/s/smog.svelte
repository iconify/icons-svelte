<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh3pkp80f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="xh3pkp80f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:smog" {...props}></Icon>
