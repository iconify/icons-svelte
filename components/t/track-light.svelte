<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o417n3brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o417n3brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:track-light" {...props}></Icon>
