<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5mhk2brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5mhk2brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:settings-3-fill" {...props}></Icon>
