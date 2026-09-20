<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gogo-nnql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gogo-nnql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:web-sync" {...props}></Icon>
