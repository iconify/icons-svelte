<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9bipf0fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9bipf0fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:view-rows-line" {...props}></Icon>
