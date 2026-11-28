<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-b4eiupb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-b4eiupb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:subscript-solid" {...props}></Icon>
