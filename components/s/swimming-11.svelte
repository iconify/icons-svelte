<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfr4dsb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="qfr4dsb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:swimming-11" {...props}></Icon>
