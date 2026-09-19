<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehtg9qbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ehtg9qbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:twitter-alt" {...props}></Icon>
