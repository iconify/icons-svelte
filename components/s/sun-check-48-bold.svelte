<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c78rfib1o.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/d/d_u133t5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c78rfib1o"/><path class="hwjgqrbah"/><path class="d_u133t5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-check-48-bold" {...props}></Icon>
