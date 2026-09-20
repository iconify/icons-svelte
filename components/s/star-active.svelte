<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym-4rinff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym-4rinff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:star-active" {...props}></Icon>
