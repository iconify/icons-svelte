<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcrgqg1rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xcrgqg1rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:square-shadow" {...props}></Icon>
