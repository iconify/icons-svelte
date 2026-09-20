<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-xgggb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="e-xgggb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:task-list-f" {...props}></Icon>
