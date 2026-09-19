<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2gnuus1q.css';
import '../../css/u/uvu1bzkib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u2gnuus1q"/><path class="uvu1bzkib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:swift" {...props}></Icon>
