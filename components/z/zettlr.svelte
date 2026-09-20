<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t55dxpbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t55dxpbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zettlr" {...props}></Icon>
