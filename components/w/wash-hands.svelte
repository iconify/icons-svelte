<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-gtufbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-gtufbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:wash-hands" {...props}></Icon>
