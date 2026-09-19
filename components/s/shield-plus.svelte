<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytyrf4ord.css';
import '../../css/i/iyx3sgnar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytyrf4ord"/><path class="iyx3sgnar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:shield-plus" {...props}></Icon>
