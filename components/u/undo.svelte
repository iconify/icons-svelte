<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ri-jboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":583,"height":716};
const content = `<path class="p7ri-jboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:undo" {...props}></Icon>
