<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1_6-jkgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary z1_6-jkgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wifi-low-duotone" {...props}></Icon>
