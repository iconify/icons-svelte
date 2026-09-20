<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruj98ub9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruj98ub9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:veepee" {...props}></Icon>
