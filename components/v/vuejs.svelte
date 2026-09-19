<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj988qb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="sj988qb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:vuejs" {...props}></Icon>
