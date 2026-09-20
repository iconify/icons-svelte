<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-gr9vbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-gr9vbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:synchronize-arrows-three-bold" {...props}></Icon>
