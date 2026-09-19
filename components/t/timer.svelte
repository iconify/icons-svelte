<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5_1g1oqt.css';
import '../../css/i/inrili5tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5_1g1oqt"/><path class="inrili5tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:timer" {...props}></Icon>
