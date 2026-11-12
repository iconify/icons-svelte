<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxhu2qlhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxhu2qlhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:text-pen" {...props}></Icon>
