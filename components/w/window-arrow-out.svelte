<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v889btb6l.css';
import '../../css/j/jd8alfe-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v889btb6l"/><path class="jd8alfe-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:window-arrow-out" {...props}></Icon>
