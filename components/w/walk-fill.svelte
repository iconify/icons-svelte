<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxxshtzvx.css';
import '../../css/m/mojdq78pj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxxshtzvx"/><path class="mojdq78pj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:walk-fill" {...props}></Icon>
