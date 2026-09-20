<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx9aw1bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx9aw1bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:task-error" {...props}></Icon>
