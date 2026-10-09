<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnpp6kxet.css';
import '../../css/o/o1nbqcbpn.css';
import '../../css/k/k8gd1dj3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fnpp6kxet"/><path class="o1nbqcbpn"/><path class="k8gd1dj3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ship-20" {...props}></Icon>
