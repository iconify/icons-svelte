<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so8gcqb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so8gcqb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:undo3-filled" {...props}></Icon>
