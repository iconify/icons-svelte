<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr4e3jb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr4e3jb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:trello" {...props}></Icon>
