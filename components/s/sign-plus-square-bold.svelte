<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oei9pubwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oei9pubwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-plus-square-bold" {...props}></Icon>
