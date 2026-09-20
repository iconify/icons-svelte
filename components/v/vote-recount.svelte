<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afiuy3b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afiuy3b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vote-recount" {...props}></Icon>
