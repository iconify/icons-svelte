<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg577rkir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg577rkir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:signal-wifi-error-fill" {...props}></Icon>
