<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ioi6o8bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ioi6o8bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:squash" {...props}></Icon>
