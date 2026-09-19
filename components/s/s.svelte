<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9q2ikbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="v9q2ikbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:s" {...props}></Icon>
