<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuapj8bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuapj8bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ts-node" {...props}></Icon>
