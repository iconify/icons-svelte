<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y85zfp33x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y85zfp33x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:wordpress" {...props}></Icon>
