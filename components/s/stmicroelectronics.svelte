<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgzc4sb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgzc4sb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:stmicroelectronics" {...props}></Icon>
