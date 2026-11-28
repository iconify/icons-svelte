<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlal61btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlal61btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sidebar-expand-solid" {...props}></Icon>
