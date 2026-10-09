<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6nu2bcpl.css';
import '../../css/t/ts55nda3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y6nu2bcpl"/><path class="ts55nda3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-48" {...props}></Icon>
