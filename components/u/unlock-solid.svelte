<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbajj74xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jbajj74xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:unlock-solid" {...props}></Icon>
