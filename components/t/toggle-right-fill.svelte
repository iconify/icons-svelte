<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfxg8vb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lfxg8vb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-right-fill" {...props}></Icon>
