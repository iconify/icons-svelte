<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyzetcb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyzetcb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:stars-c" {...props}></Icon>
