<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw8jrvyln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jw8jrvyln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tablet" {...props}></Icon>
