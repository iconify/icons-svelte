<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td7o5qxkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="td7o5qxkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:videocamera" {...props}></Icon>
