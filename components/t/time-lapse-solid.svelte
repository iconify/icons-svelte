<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9o8brmdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9o8brmdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:time-lapse-solid" {...props}></Icon>
