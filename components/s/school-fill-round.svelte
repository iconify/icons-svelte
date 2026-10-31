<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecj1oabrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecj1oabrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:school-fill-round" {...props}></Icon>
