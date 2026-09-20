<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubzmrab9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubzmrab9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:shield" {...props}></Icon>
