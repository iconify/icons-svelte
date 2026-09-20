<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-0ctjb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-0ctjb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:underscoredotjs" {...props}></Icon>
