<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht5b96bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ht5b96bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:spider" {...props}></Icon>
