<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao1b5d6rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao1b5d6rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:service-animal-2" {...props}></Icon>
