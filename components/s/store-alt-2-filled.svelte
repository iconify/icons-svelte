<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hznzg0bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hznzg0bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:store-alt-2-filled" {...props}></Icon>
