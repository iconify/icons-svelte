<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrbwxrw4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrbwxrw4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:swatch" {...props}></Icon>
