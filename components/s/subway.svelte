<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do3r89v-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="do3r89v-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:subway" {...props}></Icon>
