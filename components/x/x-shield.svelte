<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnm2d4hge.css';
import '../../css/y/yvoivnbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnm2d4hge"/><path class="yvoivnbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:x-shield" {...props}></Icon>
