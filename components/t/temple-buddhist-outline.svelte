<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fae2gzrzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fae2gzrzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:temple-buddhist-outline" {...props}></Icon>
