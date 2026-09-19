<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5fxwudtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5fxwudtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:view-columns-solid" {...props}></Icon>
