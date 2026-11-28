<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7pr4hbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7pr4hbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:sunflower-solid" {...props}></Icon>
