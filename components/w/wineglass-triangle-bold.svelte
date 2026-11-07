<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb-67rblr.css';
import '../../css/e/el5xkem2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-67rblr"/><path class="el5xkem2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wineglass-triangle-bold" {...props}></Icon>
