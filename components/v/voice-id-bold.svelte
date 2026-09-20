<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-0nqacer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-0nqacer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:voice-id-bold" {...props}></Icon>
