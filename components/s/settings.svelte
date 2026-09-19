<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co2jqtext.css';
import '../../css/w/wndsmq8hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co2jqtext duoicon-secondary-layer"/><path class="duoicon-primary-layer wndsmq8hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:settings" {...props}></Icon>
