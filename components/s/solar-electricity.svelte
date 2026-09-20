<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1fz6jjjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1fz6jjjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:solar-electricity" {...props}></Icon>
