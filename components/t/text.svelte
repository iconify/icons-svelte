<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocvuu5baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocvuu5baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:text" {...props}></Icon>
