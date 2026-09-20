<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4j0-p4on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="g4j0-p4on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:wrench-f" {...props}></Icon>
