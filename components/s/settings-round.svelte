<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csb-3693b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csb-3693b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:settings-round" {...props}></Icon>
