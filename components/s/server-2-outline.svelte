<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0knn25cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l0knn25cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:server-2-outline" {...props}></Icon>
