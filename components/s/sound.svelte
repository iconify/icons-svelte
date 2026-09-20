<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq1v7vbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq1v7vbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sound" {...props}></Icon>
