<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa4_gqbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa4_gqbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:signal-solid" {...props}></Icon>
