<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgue06l3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cgue06l3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sun-minus" {...props}></Icon>
