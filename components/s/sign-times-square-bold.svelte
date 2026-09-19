<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5zv7db-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5zv7db-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-times-square-bold" {...props}></Icon>
