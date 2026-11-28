<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy1r4hwit.css';
import '../../css/b/bkd0k5o0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy1r4hwit secondary"/><path class="bkd0k5o0y primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tiktok-duo" {...props}></Icon>
