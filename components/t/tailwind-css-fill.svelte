<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsvkrrtht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsvkrrtht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tailwind-css-fill" {...props}></Icon>
