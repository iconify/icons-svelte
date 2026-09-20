<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esij82b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esij82b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sumologic" {...props}></Icon>
