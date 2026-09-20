<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6f1imrlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6f1imrlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:video-frame-cut-bold" {...props}></Icon>
