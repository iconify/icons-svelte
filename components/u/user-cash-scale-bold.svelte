<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi7_4fbxw.css';
import '../../css/v/v4344lbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi7_4fbxw"/><path class="v4344lbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:user-cash-scale-bold" {...props}></Icon>
