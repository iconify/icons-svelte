<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je_q_ibix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="je_q_ibix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:shrink" {...props}></Icon>
