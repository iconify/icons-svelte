<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhuqvpb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qhuqvpb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:translate-hira-latin" {...props}></Icon>
