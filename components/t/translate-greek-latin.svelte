<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_7ttr2sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="b_7ttr2sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:translate-greek-latin" {...props}></Icon>
