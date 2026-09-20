<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa43sgb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa43sgb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tampermonkey" {...props}></Icon>
