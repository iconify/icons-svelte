<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnoc0t9do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnoc0t9do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seat-legroom-extra" {...props}></Icon>
