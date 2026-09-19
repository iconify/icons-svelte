<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4bwxk3ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q4bwxk3ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:triangle-check" {...props}></Icon>
