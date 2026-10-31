<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-ve0sbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ve0sbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-user-fill-round" {...props}></Icon>
