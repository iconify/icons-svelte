<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6is9iqml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6is9iqml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-line" {...props}></Icon>
