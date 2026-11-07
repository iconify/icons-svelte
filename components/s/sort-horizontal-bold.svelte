<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umzedbqyk.css';
import '../../css/d/d0h3wsgcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umzedbqyk"/><path class="d0h3wsgcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-horizontal-bold" {...props}></Icon>
