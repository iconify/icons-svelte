<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu99u_15k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qu99u_15k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-sort-horizontal-bold" {...props}></Icon>
