<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlb75okwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlb75okwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seat-legroom-reduced" {...props}></Icon>
