<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynaascbgh.css';
import '../../css/f/fephoqb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynaascbgh"/><path clip-rule="evenodd" class="fephoqb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:siderbar-outline" {...props}></Icon>
