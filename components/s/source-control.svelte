<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wub5tac1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wub5tac1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:source-control" {...props}></Icon>
