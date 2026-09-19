<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfsiw919t.css';
import '../../css/k/kqtvm-g_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfsiw919t"/><path class="kqtvm-g_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-exclude-alt" {...props}></Icon>
