<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo0wrgluc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo0wrgluc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:xml" {...props}></Icon>
