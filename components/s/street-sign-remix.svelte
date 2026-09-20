<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmx8dccer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wmx8dccer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:street-sign-remix" {...props}></Icon>
