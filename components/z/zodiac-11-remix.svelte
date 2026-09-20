<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2_nfc4uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c2_nfc4uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-11-remix" {...props}></Icon>
