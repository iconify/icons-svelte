<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3lxffb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3lxffb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ruler-pen-filled" {...props}></Icon>
