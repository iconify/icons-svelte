<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcqte1bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bcqte1bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:t-shirt-and-scissors" {...props}></Icon>
