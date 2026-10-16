<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poxn7fb3x.css';
import '../../css/h/h4vfp4baj.css';
import '../../css/p/p6isisbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="poxn7fb3x"/><path class="h4vfp4baj"/><path class="p6isisbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:transition-piece-20-bold" {...props}></Icon>
