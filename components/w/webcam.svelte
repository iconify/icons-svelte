<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugoz1lb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugoz1lb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:webcam" {...props}></Icon>
