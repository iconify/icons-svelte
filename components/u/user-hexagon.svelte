<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-kwgp5vg.css';
import '../../css/u/ujjz19bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-kwgp5vg"/><path class="ujjz19bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-hexagon" {...props}></Icon>
