<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf-i5z3nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf-i5z3nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stream-bold" {...props}></Icon>
