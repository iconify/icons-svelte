<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6hr64b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6hr64b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:snowman" {...props}></Icon>
