<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kueda4bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kueda4bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:volume-plus" {...props}></Icon>
