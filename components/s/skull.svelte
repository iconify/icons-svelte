<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiwy8cc9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hiwy8cc9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:skull" {...props}></Icon>
