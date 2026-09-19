<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p16xzgbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p16xzgbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:three-three" {...props}></Icon>
