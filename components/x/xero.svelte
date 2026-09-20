<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umxgh6bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umxgh6bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:xero" {...props}></Icon>
