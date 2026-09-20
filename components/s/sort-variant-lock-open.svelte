<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v26jpc9-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v26jpc9-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sort-variant-lock-open" {...props}></Icon>
