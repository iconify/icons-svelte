<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp51r9b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hp51r9b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:u1fad9" {...props}></Icon>
