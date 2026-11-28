<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msh8qpjuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msh8qpjuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:water-glass-plus" {...props}></Icon>
