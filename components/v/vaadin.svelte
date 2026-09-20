<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d622-7b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d622-7b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vaadin" {...props}></Icon>
