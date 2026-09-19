<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9f6rebrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9f6rebrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sleepy-filled" {...props}></Icon>
