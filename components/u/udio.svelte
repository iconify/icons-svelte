<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttr3kfbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttr3kfbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:udio" {...props}></Icon>
