<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpepx755w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hpepx755w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tfuel" {...props}></Icon>
