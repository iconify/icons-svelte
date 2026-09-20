<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu2g9iiqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu2g9iiqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:smartthings" {...props}></Icon>
