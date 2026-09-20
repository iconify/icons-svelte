<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q98t-9r5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q98t-9r5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:stop-outline" {...props}></Icon>
