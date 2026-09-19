<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk-pp3bfw.css';
import '../../css/f/f3zm4_bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk-pp3bfw"/><path class="f3zm4_bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:torus" {...props}></Icon>
