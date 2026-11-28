<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwlu0cchv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwlu0cchv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:wallet-lock" {...props}></Icon>
