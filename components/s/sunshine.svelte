<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg40qgb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg40qgb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:sunshine" {...props}></Icon>
