<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/son5b-qcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="son5b-qcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:vector-distort-solid" {...props}></Icon>
