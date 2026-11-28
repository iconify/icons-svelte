<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8mcy1yex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8mcy1yex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:syringe-solid" {...props}></Icon>
