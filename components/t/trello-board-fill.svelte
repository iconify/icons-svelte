<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j84o_8b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j84o_8b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trello-board-fill" {...props}></Icon>
