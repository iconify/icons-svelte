<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/layun2cdm.css';
import '../../css/c/cwapoj_fx.css';
import '../../css/m/m2q42tstp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="layun2cdm"/><path class="cwapoj_fx"/><path class="m2q42tstp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-angle-20-bold" {...props}></Icon>
