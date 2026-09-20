<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crs964q4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crs964q4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:saving-bank-1-bold" {...props}></Icon>
