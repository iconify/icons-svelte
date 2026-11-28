<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es_tc62ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es_tc62ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:tabs" {...props}></Icon>
