<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsl8n5bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jsl8n5bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-pinterest-outline" {...props}></Icon>
