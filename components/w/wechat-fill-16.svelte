<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh_gcb3dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fh_gcb3dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wechat-fill-16" {...props}></Icon>
