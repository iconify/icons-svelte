<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot2ejsbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot2ejsbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:scissor-2" {...props}></Icon>
