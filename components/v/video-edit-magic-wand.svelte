<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrgb9jblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrgb9jblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:video-edit-magic-wand" {...props}></Icon>
