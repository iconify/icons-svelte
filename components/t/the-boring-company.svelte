<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pypxp0b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pypxp0b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-boring-company" {...props}></Icon>
