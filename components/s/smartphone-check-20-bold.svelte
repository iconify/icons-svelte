<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veoutmb5y.css';
import '../../css/n/nutvqx2bw.css';
import '../../css/s/sh06c0bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="veoutmb5y"/><path class="nutvqx2bw"/><path class="sh06c0bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-check-20-bold" {...props}></Icon>
