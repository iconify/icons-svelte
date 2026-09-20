<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojp61_uzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojp61_uzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:search-none-fill" {...props}></Icon>
