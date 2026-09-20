<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/g/gdrayebum.css';
import '../../css/s/saw53o2qp.css';
import '../../css/d/d2xz6hb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="gdrayebum"/><path class="saw53o2qp"/><circle class="d2xz6hb5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smartphone-2-linear" {...props}></Icon>
