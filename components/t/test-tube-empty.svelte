<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cak87qbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cak87qbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:test-tube-empty" {...props}></Icon>
