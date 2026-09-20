<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc4mb0wfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc4mb0wfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-x-line" {...props}></Icon>
