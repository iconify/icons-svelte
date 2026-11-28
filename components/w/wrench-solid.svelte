<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1xp4e_uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1xp4e_uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wrench-solid" {...props}></Icon>
