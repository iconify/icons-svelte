<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arew0hbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arew0hbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:source-code" {...props}></Icon>
