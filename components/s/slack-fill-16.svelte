<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzfpc1bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xzfpc1bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:slack-fill-16" {...props}></Icon>
