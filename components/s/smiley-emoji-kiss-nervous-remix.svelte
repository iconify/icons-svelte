<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcpkz9k_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wcpkz9k_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-emoji-kiss-nervous-remix" {...props}></Icon>
