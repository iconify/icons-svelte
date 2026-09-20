<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzr7vhb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzr7vhb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:todo-line" {...props}></Icon>
