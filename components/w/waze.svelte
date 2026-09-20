<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzt-hibdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzt-hibdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:waze" {...props}></Icon>
