<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl3jor9cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl3jor9cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:toaster" {...props}></Icon>
