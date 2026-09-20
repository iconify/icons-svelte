<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r58y-acsy.css';
import '../../css/x/xqiik-79j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r58y-acsy"/><path class="xqiik-79j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rtm" {...props}></Icon>
