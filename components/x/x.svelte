<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsulv59-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsulv59-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:x" {...props}></Icon>
