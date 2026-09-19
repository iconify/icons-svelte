<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8bb03b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m8bb03b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:suspension-railway" {...props}></Icon>
