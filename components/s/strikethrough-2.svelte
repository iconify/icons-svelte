<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koy2ms7jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="koy2ms7jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:strikethrough-2" {...props}></Icon>
