<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx4qrdfct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx4qrdfct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:search-bar-remix" {...props}></Icon>
