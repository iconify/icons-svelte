<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg9366z8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg9366z8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:video-line" {...props}></Icon>
