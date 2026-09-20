<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7p6xjb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7p6xjb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sign-text" {...props}></Icon>
