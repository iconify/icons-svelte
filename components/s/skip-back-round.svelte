<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kocz6pb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kocz6pb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-back-round" {...props}></Icon>
