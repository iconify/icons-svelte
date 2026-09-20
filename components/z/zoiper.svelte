<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbbc0ebce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbbc0ebce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:zoiper" {...props}></Icon>
