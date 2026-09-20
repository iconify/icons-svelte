<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqt1wjcwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqt1wjcwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:text-bar" {...props}></Icon>
