<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufl8c1dfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufl8c1dfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:undo" {...props}></Icon>
