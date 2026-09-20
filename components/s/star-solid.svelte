<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in0jig21n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in0jig21n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:star-solid" {...props}></Icon>
