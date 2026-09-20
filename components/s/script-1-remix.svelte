<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydwy7o8kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydwy7o8kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:script-1-remix" {...props}></Icon>
