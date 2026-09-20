<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_-in-bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_-in-bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ruff" {...props}></Icon>
