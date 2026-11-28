<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyu_nlhsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyu_nlhsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:server-off" {...props}></Icon>
