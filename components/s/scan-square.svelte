<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4eytjb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4eytjb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scan-square" {...props}></Icon>
