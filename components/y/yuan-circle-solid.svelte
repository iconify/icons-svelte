<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f52ia3bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f52ia3bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:yuan-circle-solid" {...props}></Icon>
