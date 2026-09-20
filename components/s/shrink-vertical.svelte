<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmjzb8d8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmjzb8d8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:shrink-vertical" {...props}></Icon>
