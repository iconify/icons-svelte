<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3wds3ztu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c3wds3ztu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:two-of-bamboos-mahjong-filled" {...props}></Icon>
