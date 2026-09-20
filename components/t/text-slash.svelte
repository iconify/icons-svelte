<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk9o850it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk9o850it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:text-slash" {...props}></Icon>
