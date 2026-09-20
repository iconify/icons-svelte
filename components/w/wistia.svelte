<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjnnw855e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjnnw855e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wistia" {...props}></Icon>
