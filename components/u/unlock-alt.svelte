<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqungccnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqungccnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:unlock-alt" {...props}></Icon>
