<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi-u46bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi-u46bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:xtz-fill" {...props}></Icon>
