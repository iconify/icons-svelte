<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g09n5j3dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g09n5j3dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ubiquiti-ap" {...props}></Icon>
