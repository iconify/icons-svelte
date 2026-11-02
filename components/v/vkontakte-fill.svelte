<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg4wjbxkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg4wjbxkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vkontakte-fill" {...props}></Icon>
