<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7kfprb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7kfprb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:zodiac-aries" {...props}></Icon>
