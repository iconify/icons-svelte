<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sng-n9b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sng-n9b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-minus-duotone" {...props}></Icon>
