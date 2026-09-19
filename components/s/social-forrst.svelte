<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnqtz66sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="hnqtz66sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-forrst" {...props}></Icon>
