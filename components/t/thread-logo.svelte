<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi3905b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qi3905b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:thread-logo" {...props}></Icon>
