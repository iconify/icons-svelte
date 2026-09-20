<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp45jb.css';
import '../../css/d/d-t9c80f.css';
import '../../css/s/so-from-34.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp45jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-pulsating-loop" {...props}></Icon>
