<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdt_2mbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdt_2mbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:totvs" {...props}></Icon>
