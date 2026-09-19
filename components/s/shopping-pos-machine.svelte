<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcdw70s4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":24};
const content = `<path class="hcdw70s4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopping-pos-machine" {...props}></Icon>
