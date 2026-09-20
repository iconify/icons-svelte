<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m73gp0u2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m73gp0u2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-price-bold" {...props}></Icon>
