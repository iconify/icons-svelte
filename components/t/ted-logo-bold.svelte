<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy0q25fis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy0q25fis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:ted-logo-bold" {...props}></Icon>
