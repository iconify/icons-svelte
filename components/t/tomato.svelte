<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-erwfbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="q-erwfbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:tomato" {...props}></Icon>
