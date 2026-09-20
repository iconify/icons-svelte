<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psb2m6b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="psb2m6b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:speaker-1-remix" {...props}></Icon>
