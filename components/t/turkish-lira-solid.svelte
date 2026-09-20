<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmuay5b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmuay5b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:turkish-lira-solid" {...props}></Icon>
