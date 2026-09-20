<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3a39im_l.css';
import '../../css/t/tp_oyib9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3a39im_l"/><path class="tp_oyib9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trello-board-line" {...props}></Icon>
