<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq7z04bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq7z04bxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:up" {...props}></Icon>
