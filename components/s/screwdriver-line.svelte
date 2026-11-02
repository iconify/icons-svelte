<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psp9dbjum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psp9dbjum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:screwdriver-line" {...props}></Icon>
