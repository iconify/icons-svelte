<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc28web6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc28web6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wrap-text" {...props}></Icon>
