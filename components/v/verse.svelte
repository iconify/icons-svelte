<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/ngekvelpk.css';
import '../../css/k/kga49o1gr.css';
import '../../css/y/ykp8htwkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ngekvelpk"/><path class="kga49o1gr"/><path class="ykp8htwkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:verse" {...props}></Icon>
