<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmm2mib0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="cmm2mib0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:volume-up-square-f" {...props}></Icon>
