<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl04g7bka.css';
import '../../css/u/uffvvac3n.css';
import '../../css/z/ze1765b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pl04g7bka"/><path class="uffvvac3n"/><path class="ze1765b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:version" {...props}></Icon>
