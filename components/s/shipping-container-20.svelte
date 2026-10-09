<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3qrw7b3x.css';
import '../../css/n/n2w7bjvhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k3qrw7b3x"/><path class="n2w7bjvhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:shipping-container-20" {...props}></Icon>
