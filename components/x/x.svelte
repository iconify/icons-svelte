<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyjbqfh7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyjbqfh7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:x" {...props}></Icon>
