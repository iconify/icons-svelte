<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw-q_obqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hw-q_obqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:strawberry" {...props}></Icon>
