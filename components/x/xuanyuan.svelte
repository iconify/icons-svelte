<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox05h0bip.css';
import '../../css/t/t5n35bb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox05h0bip"/><path class="t5n35bb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xuanyuan" {...props}></Icon>
