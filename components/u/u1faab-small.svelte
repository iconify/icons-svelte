<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmjoq-bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hmjoq-bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:u1faab-small" {...props}></Icon>
