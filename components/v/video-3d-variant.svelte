<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3hs87bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3hs87bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-3d-variant" {...props}></Icon>
