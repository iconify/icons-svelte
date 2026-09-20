<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3y-bwxly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w3y-bwxly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:screen-tv-remix" {...props}></Icon>
