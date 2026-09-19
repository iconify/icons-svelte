<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yax0ei6je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yax0ei6je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:users" {...props}></Icon>
