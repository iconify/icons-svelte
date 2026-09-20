<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7rd43bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7rd43bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vkontakte-box" {...props}></Icon>
