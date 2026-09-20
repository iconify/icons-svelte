<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndwl507qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndwl507qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:signal" {...props}></Icon>
