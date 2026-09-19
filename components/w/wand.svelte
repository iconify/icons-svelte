<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r39id2hno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r39id2hno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:wand" {...props}></Icon>
