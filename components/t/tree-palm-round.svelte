<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g21x4li4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g21x4li4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tree-palm-round" {...props}></Icon>
