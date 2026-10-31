<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il8tallos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il8tallos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sprout-gloss" {...props}></Icon>
