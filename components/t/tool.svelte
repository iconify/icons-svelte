<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aofh0lbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aofh0lbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tool" {...props}></Icon>
