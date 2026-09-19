<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h38xtl-6m.css';
import '../../css/z/z3me40b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h38xtl-6m"/><path class="z3me40b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:skull" {...props}></Icon>
