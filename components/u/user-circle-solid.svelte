<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm5og6r_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm5og6r_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:user-circle-solid" {...props}></Icon>
