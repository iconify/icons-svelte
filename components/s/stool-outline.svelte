<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd0l-6ivh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sd0l-6ivh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stool-outline" {...props}></Icon>
