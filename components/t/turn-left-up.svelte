<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz1or2rab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz1or2rab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:turn-left-up" {...props}></Icon>
