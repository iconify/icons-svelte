<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw6ha2eoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw6ha2eoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:skyatlas" {...props}></Icon>
