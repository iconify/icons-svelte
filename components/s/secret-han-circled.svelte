<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2k03x09g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h2k03x09g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:secret-han-circled" {...props}></Icon>
