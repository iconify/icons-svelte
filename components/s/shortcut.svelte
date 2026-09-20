<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j25opi_1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j25opi_1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:shortcut" {...props}></Icon>
