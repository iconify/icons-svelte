<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqc2c8bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqc2c8bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:thumb-down" {...props}></Icon>
