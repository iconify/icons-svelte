<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df4k46fvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="df4k46fvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:strong" {...props}></Icon>
