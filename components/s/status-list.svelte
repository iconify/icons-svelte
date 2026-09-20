<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en96x3gyh.css';
import '../../css/h/h68a5vtzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="en96x3gyh"/><circle class="h68a5vtzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:status-list" {...props}></Icon>
