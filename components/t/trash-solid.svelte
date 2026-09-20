<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-2odwape.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-2odwape"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:trash-solid" {...props}></Icon>
