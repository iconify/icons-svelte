<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzj8i4mvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1080};
const content = `<path clip-rule="evenodd" class="tzj8i4mvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:wash-bicycle-14" {...props}></Icon>
