<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkd3jjpvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gkd3jjpvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-4-remix" {...props}></Icon>
