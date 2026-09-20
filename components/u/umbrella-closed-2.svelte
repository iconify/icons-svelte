<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_9cgd51r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_9cgd51r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:umbrella-closed-2" {...props}></Icon>
