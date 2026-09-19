<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z59vvfb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z59vvfb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:translate-latin-han" {...props}></Icon>
