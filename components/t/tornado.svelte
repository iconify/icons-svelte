<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzn940boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzn940boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:tornado" {...props}></Icon>
