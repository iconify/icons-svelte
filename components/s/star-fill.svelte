<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xugmi0cit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xugmi0cit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:star-fill" {...props}></Icon>
