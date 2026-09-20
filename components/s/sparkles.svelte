<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjw3e_ued.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjw3e_ued"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:sparkles" {...props}></Icon>
