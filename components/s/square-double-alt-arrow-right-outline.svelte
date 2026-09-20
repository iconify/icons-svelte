<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3vjmwkjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3vjmwkjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-double-alt-arrow-right-outline" {...props}></Icon>
