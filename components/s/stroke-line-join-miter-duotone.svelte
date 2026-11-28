<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdm67zyal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wdm67zyal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stroke-line-join-miter-duotone" {...props}></Icon>
