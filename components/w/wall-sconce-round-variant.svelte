<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njo4stv8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njo4stv8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wall-sconce-round-variant" {...props}></Icon>
