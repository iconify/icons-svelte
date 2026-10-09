<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgcb4c_nz.css';
import '../../css/c/ctkosrb3v.css';
import '../../css/l/lxsqj045t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jgcb4c_nz"/><path class="ctkosrb3v"/><path class="lxsqj045t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-lock-20-bold" {...props}></Icon>
