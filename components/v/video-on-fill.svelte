<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb7l0mbjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb7l0mbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-on-fill" {...props}></Icon>
