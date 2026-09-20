<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhes_pini.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dhes_pini"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-circle" {...props}></Icon>
