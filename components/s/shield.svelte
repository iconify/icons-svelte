<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffvcs0yvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="ffvcs0yvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shield" {...props}></Icon>
