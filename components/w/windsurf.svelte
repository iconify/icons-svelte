<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ratl6yjby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ratl6yjby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:windsurf" {...props}></Icon>
