<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udqirj5ye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udqirj5ye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:vector-difference-ba" {...props}></Icon>
