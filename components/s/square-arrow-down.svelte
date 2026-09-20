<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3v1tk3gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3v1tk3gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrow-down" {...props}></Icon>
