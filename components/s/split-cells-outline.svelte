<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgj4h-bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgj4h-bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:split-cells-outline" {...props}></Icon>
