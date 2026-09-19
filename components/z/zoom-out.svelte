<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoppgiqnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoppgiqnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:zoom-out" {...props}></Icon>
