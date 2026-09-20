<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgh4-s7mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgh4-s7mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ruble-outline" {...props}></Icon>
