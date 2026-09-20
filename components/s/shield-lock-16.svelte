<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrw6ywbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zrw6ywbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:shield-lock-16" {...props}></Icon>
