<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpmfcobat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpmfcobat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:salad-check" {...props}></Icon>
