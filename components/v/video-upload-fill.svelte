<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydkqw95qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydkqw95qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:video-upload-fill" {...props}></Icon>
