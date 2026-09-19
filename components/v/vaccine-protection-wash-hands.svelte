<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3u3rrbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3u3rrbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:vaccine-protection-wash-hands" {...props}></Icon>
