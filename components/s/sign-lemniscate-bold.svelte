<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtv6wdbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtv6wdbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-lemniscate-bold" {...props}></Icon>
