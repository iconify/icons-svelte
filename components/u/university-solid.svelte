<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypp5vkmzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ypp5vkmzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:university-solid" {...props}></Icon>
