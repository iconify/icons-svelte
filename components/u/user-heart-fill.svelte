<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahbxdqfbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahbxdqfbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-heart-fill" {...props}></Icon>
