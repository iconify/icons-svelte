<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7yoyjuni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7yoyjuni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:type-solid" {...props}></Icon>
