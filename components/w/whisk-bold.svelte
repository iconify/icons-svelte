<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu8v03boj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vu8v03boj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:whisk-bold" {...props}></Icon>
