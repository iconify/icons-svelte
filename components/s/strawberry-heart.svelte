<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aozbnhbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aozbnhbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:strawberry-heart" {...props}></Icon>
