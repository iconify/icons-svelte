<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of9ozfbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="of9ozfbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:routing-3-outline" {...props}></Icon>
