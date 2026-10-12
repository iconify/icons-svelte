<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cloedsmpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cloedsmpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:the-lampster" {...props}></Icon>
