<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-c6jlbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-c6jlbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:user-plus-solid" {...props}></Icon>
