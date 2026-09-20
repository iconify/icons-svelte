<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkzjx8nae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkzjx8nae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tauri" {...props}></Icon>
