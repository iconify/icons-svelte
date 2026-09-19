<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5fqd7-mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5fqd7-mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:samsung-serif-stand" {...props}></Icon>
