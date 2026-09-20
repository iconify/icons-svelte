<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez72gdcxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez72gdcxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shredder" {...props}></Icon>
