<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtzcwg7gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtzcwg7gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:spacing-vertical-fill" {...props}></Icon>
