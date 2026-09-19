<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7yr2gb8r.css';
import '../../css/i/if9yuik-y.css';
import '../../css/g/g3e_4lbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n7yr2gb8r"/><path class="if9yuik-y"/><path class="g3e_4lbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vitest" {...props}></Icon>
