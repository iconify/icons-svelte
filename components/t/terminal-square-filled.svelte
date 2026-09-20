<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0v27dbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v0v27dbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:terminal-square-filled" {...props}></Icon>
