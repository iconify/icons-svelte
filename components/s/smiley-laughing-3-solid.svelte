<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-w7k98js.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f-w7k98js"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-laughing-3-solid" {...props}></Icon>
