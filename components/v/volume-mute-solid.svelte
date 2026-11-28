<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6c7hlb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6c7hlb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:volume-mute-solid" {...props}></Icon>
