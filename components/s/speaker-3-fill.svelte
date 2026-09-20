<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwp2pllyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwp2pllyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:speaker-3-fill" {...props}></Icon>
