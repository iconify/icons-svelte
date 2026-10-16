<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9rw-n5ub.css';
import '../../css/n/nyre3sbly.css';
import '../../css/k/kzevrep2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a9rw-n5ub"/><path class="nyre3sbly"/><path class="kzevrep2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:settlement-48-bold" {...props}></Icon>
