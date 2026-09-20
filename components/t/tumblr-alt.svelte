<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxqzdbbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxqzdbbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:tumblr-alt" {...props}></Icon>
