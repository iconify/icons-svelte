<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrx7p7gdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrx7p7gdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:spinner" {...props}></Icon>
