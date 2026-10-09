<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvf62xf5g.css';
import '../../css/k/k-8tebcux.css';
import '../../css/g/gz2x7rbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vvf62xf5g"/><path class="k-8tebcux"/><path class="gz2x7rbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:screw-20-bold" {...props}></Icon>
