<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-5x-acls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-5x-acls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:watch-solid" {...props}></Icon>
