<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov2igo9rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov2igo9rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:star5" {...props}></Icon>
