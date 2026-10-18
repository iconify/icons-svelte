<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpj3_ybqz.css';
import '../../css/v/v_f07jpah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kpj3_ybqz"/><path class="v_f07jpah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seaweed-20-bold" {...props}></Icon>
