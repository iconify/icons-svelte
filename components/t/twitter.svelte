<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzc9ocbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzc9ocbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:twitter" {...props}></Icon>
