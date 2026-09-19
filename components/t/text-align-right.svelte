<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owp06vahj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owp06vahj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:text-align-right" {...props}></Icon>
