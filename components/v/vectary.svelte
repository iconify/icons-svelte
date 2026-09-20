<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grn-okb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grn-okb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vectary" {...props}></Icon>
