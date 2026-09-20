<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvf2eacwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xvf2eacwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tent" {...props}></Icon>
