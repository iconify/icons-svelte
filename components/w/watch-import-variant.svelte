<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms5m7db0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms5m7db0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:watch-import-variant" {...props}></Icon>
