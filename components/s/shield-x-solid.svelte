<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhumhpb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhumhpb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-x-solid" {...props}></Icon>
