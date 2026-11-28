<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q39dj8bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q39dj8bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:unlink-solid" {...props}></Icon>
