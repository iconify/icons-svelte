<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvx8sibzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvx8sibzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smile" {...props}></Icon>
