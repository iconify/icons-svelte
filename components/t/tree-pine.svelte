<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay53_oboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay53_oboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tree-pine" {...props}></Icon>
