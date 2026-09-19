<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc5busrsc.css';
import '../../css/o/oim_e1bef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc5busrsc"/><path class="oim_e1bef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:save-fill" {...props}></Icon>
