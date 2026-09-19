<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqc_2glev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqc_2glev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:server-outline" {...props}></Icon>
