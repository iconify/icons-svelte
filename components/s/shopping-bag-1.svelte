<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2wo1bdya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="j2wo1bdya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:shopping-bag-1" {...props}></Icon>
