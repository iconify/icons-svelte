<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6y4_z34g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6y4_z34g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-user" {...props}></Icon>
