<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svahi-bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svahi-bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:unraid" {...props}></Icon>
