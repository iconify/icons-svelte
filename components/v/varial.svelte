<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uemridbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uemridbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:varial" {...props}></Icon>
