<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fapr92-oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fapr92-oh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:velocity" {...props}></Icon>
