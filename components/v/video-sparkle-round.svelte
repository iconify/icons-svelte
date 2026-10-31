<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu_zi1wud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu_zi1wud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:video-sparkle-round" {...props}></Icon>
