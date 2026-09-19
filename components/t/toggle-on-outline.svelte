<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4s7832oy.css';
import '../../css/a/alcoyobza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4s7832oy"/><path clip-rule="evenodd" class="alcoyobza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:toggle-on-outline" {...props}></Icon>
