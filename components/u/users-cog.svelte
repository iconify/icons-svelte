<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo53tqi5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo53tqi5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users-cog" {...props}></Icon>
