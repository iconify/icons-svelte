<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqq4c7qxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqq4c7qxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:transmission-bt" {...props}></Icon>
