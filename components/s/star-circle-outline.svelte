<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqm37pb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fqm37pb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:star-circle-outline" {...props}></Icon>
