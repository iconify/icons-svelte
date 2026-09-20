<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grzqycbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grzqycbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:signal-app" {...props}></Icon>
