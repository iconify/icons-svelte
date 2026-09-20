<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3oxki-oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3oxki-oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smiley-sad-outline" {...props}></Icon>
