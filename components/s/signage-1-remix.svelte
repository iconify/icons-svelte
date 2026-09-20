<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la3e5vmdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="la3e5vmdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:signage-1-remix" {...props}></Icon>
