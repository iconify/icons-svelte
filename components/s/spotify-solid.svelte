<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u59rcgy1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u59rcgy1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:spotify-solid" {...props}></Icon>
