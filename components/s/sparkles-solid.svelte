<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuzru93kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuzru93kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:sparkles-solid" {...props}></Icon>
