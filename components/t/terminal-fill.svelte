<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zki1cob0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zki1cob0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terminal-fill" {...props}></Icon>
