<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlcegacoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":667};
const content = `<path class="dlcegacoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:sync" {...props}></Icon>
