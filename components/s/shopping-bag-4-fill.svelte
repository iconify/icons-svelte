<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msney2gri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msney2gri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:shopping-bag-4-fill" {...props}></Icon>
