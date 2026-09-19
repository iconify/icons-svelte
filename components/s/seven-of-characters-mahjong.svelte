<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbqeu9bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zbqeu9bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:seven-of-characters-mahjong" {...props}></Icon>
