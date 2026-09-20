<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4h3mqyon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4h3mqyon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:user-work-laptop-wifi-remix" {...props}></Icon>
