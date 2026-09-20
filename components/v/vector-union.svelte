<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgx5izb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgx5izb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-union" {...props}></Icon>
