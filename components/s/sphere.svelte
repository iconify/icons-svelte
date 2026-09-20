<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxedi4h6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxedi4h6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sphere" {...props}></Icon>
