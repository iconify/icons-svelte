<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf8c-4gvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf8c-4gvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:washing-machine-x" {...props}></Icon>
