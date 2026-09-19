<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn27lybeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sn27lybeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:sliderasc" {...props}></Icon>
