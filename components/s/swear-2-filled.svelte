<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt0r02b_r.css';
import '../../css/m/mq4ja3bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt0r02b_r"/><path class="mq4ja3bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:swear-2-filled" {...props}></Icon>
