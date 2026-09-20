<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk8b46bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jk8b46bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:tiktok-logo-block" {...props}></Icon>
