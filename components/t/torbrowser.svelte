<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7o7ahd3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7o7ahd3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:torbrowser" {...props}></Icon>
