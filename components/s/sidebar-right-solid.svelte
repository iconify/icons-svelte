<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj2wdoxqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nj2wdoxqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sidebar-right-solid" {...props}></Icon>
