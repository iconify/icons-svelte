<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv1wbeblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dv1wbeblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:zoom-in" {...props}></Icon>
