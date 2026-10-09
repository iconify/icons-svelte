<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3jqfmhas.css';
import '../../css/h/hpn385b9j.css';
import '../../css/w/wyp81zbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k3jqfmhas"/><path class="hpn385b9j"/><path class="wyp81zbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:running-20-bold" {...props}></Icon>
