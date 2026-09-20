<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajjt2vrag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajjt2vrag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scania" {...props}></Icon>
