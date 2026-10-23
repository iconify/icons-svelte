<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbt8h-bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbt8h-bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-x" {...props}></Icon>
