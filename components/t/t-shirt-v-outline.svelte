<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyqt1zbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyqt1zbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:t-shirt-v-outline" {...props}></Icon>
