<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdw2rotvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bdw2rotvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-minus" {...props}></Icon>
