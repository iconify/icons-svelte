<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umwmrmjbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umwmrmjbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:windows-logo-fill-round" {...props}></Icon>
