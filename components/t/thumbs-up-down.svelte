<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot90mmbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot90mmbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:thumbs-up-down" {...props}></Icon>
