<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulohrubuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulohrubuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:standing-desk-fill-round" {...props}></Icon>
