<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cibunmorz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cibunmorz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:volume-down-outline" {...props}></Icon>
