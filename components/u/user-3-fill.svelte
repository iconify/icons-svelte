<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st7p79bzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st7p79bzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-3-fill" {...props}></Icon>
