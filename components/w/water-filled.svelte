<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcf5jt.css';
import '../../css/w/w1kvfb.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-22.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcf5jt"/><path class="w1kvfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:water-filled" {...props}></Icon>
