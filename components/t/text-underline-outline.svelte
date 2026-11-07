<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_uvt8bwv.css';
import '../../css/m/mdftclbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_uvt8bwv"/><path class="mdftclbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-underline-outline" {...props}></Icon>
