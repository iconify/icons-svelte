<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-5luxqit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-5luxqit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:server-2-fill" {...props}></Icon>
