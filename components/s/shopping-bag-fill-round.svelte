<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaobu8b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vaobu8b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-bag-fill-round" {...props}></Icon>
