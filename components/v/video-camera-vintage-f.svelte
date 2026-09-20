<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tym57sy9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="tym57sy9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:video-camera-vintage-f" {...props}></Icon>
