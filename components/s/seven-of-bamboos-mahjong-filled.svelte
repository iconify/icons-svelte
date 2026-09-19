<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxlkw4i9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bxlkw4i9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:seven-of-bamboos-mahjong-filled" {...props}></Icon>
