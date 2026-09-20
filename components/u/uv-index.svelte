<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr2wve6of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mr2wve6of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:uv-index" {...props}></Icon>
