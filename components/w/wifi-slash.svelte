<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuax2_bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuax2_bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:wifi-slash" {...props}></Icon>
