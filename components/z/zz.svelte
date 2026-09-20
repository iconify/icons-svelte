<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbcc0f97s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbcc0f97s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:zz" {...props}></Icon>
