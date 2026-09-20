<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5u2ubufd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5u2ubufd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:variable-box" {...props}></Icon>
