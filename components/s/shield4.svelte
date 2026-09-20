<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3ues5odh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3ues5odh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield4" {...props}></Icon>
