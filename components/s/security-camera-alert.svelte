<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esmp9hbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esmp9hbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:security-camera-alert" {...props}></Icon>
