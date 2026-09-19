<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hurs0qbuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hurs0qbuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:three-of-characters-mahjong" {...props}></Icon>
