<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj4366b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hj4366b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:sticky" {...props}></Icon>
