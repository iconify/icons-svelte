<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ring6vbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ring6vbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:settings-solid" {...props}></Icon>
