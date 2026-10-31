<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-m-5x5bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-m-5x5bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:webhook-fill-round" {...props}></Icon>
