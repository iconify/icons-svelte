<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3yy1_2al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p3yy1_2al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:underline" {...props}></Icon>
