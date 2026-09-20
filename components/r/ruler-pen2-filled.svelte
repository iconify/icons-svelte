<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzqhjqb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzqhjqb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ruler-pen2-filled" {...props}></Icon>
