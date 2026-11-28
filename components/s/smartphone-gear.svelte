<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bno-e-txj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bno-e-txj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smartphone-gear" {...props}></Icon>
