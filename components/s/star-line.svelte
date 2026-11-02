<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idk2wblek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idk2wblek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:star-line" {...props}></Icon>
