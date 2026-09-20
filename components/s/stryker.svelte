<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5m-lqb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5m-lqb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stryker" {...props}></Icon>
