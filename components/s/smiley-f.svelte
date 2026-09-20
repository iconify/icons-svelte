<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt6k4ej1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1.5};
const content = `<path class="zt6k4ej1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:smiley-f" {...props}></Icon>
