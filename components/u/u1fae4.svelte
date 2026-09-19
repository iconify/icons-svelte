<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njcg00bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="njcg00bym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:u1fae4" {...props}></Icon>
