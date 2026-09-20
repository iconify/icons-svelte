<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mktx9y2zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mktx9y2zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:winding-way" {...props}></Icon>
