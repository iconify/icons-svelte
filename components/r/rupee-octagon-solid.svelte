<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkmn4cfof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkmn4cfof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rupee-octagon-solid" {...props}></Icon>
