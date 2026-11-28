<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2z348odr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2z348odr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vine-solid" {...props}></Icon>
