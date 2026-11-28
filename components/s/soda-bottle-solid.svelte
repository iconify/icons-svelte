<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwb00usql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwb00usql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:soda-bottle-solid" {...props}></Icon>
