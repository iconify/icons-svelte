<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3lp20htv.css';
import '../../css/k/k9l_q1t_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z3lp20htv"/><path class="k9l_q1t_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:video-48-bold" {...props}></Icon>
