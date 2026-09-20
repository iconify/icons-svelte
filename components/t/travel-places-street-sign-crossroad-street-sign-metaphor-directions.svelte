<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fngc6jfhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fngc6jfhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-places-street-sign-crossroad-street-sign-metaphor-directions" {...props}></Icon>
