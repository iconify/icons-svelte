<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b10s5pbto.css';
import '../../css/j/japh7m8wk.css';
import '../../css/w/w1l08d2zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b10s5pbto"/><path class="japh7m8wk"/><path class="w1l08d2zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speaker-48-bold" {...props}></Icon>
