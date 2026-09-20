<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvzl2lb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvzl2lb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-minus" {...props}></Icon>
