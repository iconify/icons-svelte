<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtgg2kbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtgg2kbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:whistle" {...props}></Icon>
