<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln9rcsbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln9rcsbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:taxi-fill-round" {...props}></Icon>
