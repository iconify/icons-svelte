<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvt4khnuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tvt4khnuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:table-caption" {...props}></Icon>
