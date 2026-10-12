<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z35ia5jrg.css';
import '../../css/p/p8lm6n71m.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z35ia5jrg"/><path class="p8lm6n71m"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-check-48" {...props}></Icon>
