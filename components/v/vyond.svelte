<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m28r9ibhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m28r9ibhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:vyond" {...props}></Icon>
