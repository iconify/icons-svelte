<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_rvpzb5b.css';
import '../../css/v/vtogzbcjl.css';
import '../../css/h/hyap0y3ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n_rvpzb5b"/><path class="vtogzbcjl"/><path class="hyap0y3ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:switch-closed-20" {...props}></Icon>
