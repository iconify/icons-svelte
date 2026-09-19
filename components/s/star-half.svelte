<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhgab4ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":832,"height":1600};
const content = `<path class="qhgab4ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:star-half" {...props}></Icon>
