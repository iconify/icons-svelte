<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he_ewtb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he_ewtb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tally-3-solid" {...props}></Icon>
