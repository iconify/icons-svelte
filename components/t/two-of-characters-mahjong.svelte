<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/celtzhb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="celtzhb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:two-of-characters-mahjong" {...props}></Icon>
