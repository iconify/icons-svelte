<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu5zp6fme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu5zp6fme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tooltip" {...props}></Icon>
