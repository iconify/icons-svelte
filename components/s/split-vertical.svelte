<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz9hq19to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz9hq19to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:split-vertical" {...props}></Icon>
