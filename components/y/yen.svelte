<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3d6jdbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1408};
const content = `<path class="b3d6jdbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:yen" {...props}></Icon>
