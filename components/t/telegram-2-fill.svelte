<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agbrvlb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agbrvlb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:telegram-2-fill" {...props}></Icon>
