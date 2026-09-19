<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_-3zpb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_-3zpb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:warning-circle" {...props}></Icon>
