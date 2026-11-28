<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaimmzbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qaimmzbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:stairs-duotone" {...props}></Icon>
