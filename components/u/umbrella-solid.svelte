<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md9mqdmzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md9mqdmzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:umbrella-solid" {...props}></Icon>
