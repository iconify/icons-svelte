<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7sl9q-7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f7sl9q-7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wifi-disabled-solid" {...props}></Icon>
