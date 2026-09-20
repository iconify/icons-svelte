<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e50f1vnnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e50f1vnnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:undertale" {...props}></Icon>
