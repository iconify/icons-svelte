<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-apb-bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-apb-bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:setting-vert" {...props}></Icon>
