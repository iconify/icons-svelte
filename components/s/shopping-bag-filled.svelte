<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrg6hlbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrg6hlbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-bag-filled" {...props}></Icon>
