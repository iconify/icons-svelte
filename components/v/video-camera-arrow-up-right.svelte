<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a56926qld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a56926qld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:video-camera-arrow-up-right" {...props}></Icon>
