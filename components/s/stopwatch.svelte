<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms3tv4bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ms3tv4bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:stopwatch" {...props}></Icon>
