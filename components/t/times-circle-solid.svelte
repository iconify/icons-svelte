<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcd09qz-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcd09qz-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:times-circle-solid" {...props}></Icon>
