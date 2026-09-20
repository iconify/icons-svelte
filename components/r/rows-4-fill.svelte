<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th8jjfbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th8jjfbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rows-4-fill" {...props}></Icon>
